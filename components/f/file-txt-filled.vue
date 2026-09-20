<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co9totb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co9totb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-txt-filled" /></template>
