<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoxjszbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoxjszbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-upload-check" /></template>
