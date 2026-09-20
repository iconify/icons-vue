<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8_mbim6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8_mbim6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-image-line" /></template>
