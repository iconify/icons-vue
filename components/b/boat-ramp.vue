<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5qcd1b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="j5qcd1b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:boat-ramp" /></template>
