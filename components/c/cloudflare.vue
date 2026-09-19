<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo3h003kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="eo3h003kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:cloudflare" /></template>
