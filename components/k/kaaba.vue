<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro1l_sqac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ro1l_sqac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:kaaba" /></template>
