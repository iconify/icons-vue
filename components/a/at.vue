<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q718doyav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="q718doyav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:at" /></template>
