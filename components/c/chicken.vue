<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3_gg71sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="q3_gg71sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:chicken" /></template>
