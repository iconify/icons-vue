<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvk-evblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvk-evblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:coursera" /></template>
