<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1ey-fprr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1ey-fprr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-image-remove" /></template>
