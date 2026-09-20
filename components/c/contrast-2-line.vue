<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrgkkvb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrgkkvb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contrast-2-line" /></template>
