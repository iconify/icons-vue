<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyhwi6yfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyhwi6yfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:film-line" /></template>
