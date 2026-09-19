<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0anp0nkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m0anp0nkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:developer-tools" /></template>
