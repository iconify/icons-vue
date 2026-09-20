<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjt0m6brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjt0m6brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:crown5-filled" /></template>
