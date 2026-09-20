<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2r3i0s8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2r3i0s8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-image-filled" /></template>
