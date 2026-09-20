<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwqioovyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwqioovyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:checkbox-multiple-blank-fill" /></template>
