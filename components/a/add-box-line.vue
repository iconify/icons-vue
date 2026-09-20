<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yos525bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yos525bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:add-box-line" /></template>
