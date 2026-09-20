<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp8cl2adt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp8cl2adt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:download-line" /></template>
