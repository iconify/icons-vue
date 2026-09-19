<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu1_2j5-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gu1_2j5-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:home-group" /></template>
