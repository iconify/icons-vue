<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gplgdq1bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gplgdq1bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:align-center" /></template>
