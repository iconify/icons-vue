<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au1n8ebss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au1n8ebss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:link-unlink" /></template>
