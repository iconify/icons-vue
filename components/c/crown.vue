<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_boytb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1472};
const content = `<path class="g_boytb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:crown" /></template>
