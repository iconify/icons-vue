<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt-fotbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt-fotbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-3-line" /></template>
