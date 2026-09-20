<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu9fc8cxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu9fc8cxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:finder-fill" /></template>
