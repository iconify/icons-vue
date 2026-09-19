<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2j_6wewx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1568,"height":1824};
const content = `<path class="r2j_6wewx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:grapes" /></template>
