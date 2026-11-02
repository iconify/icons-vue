<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrx_7bb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrx_7bb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:album-2-fill" /></template>
