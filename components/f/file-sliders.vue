<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp2-p1nqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp2-p1nqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-sliders" /></template>
