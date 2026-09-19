<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0flmbb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="v0flmbb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-circle-left" /></template>
