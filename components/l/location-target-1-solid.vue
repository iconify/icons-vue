<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q66_a9bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q66_a9bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:location-target-1-solid" /></template>
