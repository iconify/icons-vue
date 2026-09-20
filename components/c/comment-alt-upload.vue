<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnw-p-byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnw-p-byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-upload" /></template>
