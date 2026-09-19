<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlrl7bbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xlrl7bbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:external" /></template>
