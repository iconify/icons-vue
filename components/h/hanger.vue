<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl1raybud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl1raybud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hanger" /></template>
