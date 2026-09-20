<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2_jcgb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d2_jcgb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:analysis-filled" /></template>
