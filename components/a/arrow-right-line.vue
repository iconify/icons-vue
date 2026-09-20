<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpuf93gxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpuf93gxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-right-line" /></template>
