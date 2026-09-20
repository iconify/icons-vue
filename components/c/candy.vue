<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imstw9b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="imstw9b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:candy" /></template>
