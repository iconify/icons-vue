<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn6u-tb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn6u-tb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:api" /></template>
