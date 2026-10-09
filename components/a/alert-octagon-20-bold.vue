<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0q12sb0a.css';
import '../../css/r/r4qnuebsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d0q12sb0a"/><path class="r4qnuebsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alert-octagon-20-bold" /></template>
