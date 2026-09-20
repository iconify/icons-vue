<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs81t-brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs81t-brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-square-solid" /></template>
