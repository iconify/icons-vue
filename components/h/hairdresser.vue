<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weokkbcgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="weokkbcgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:hairdresser" /></template>
