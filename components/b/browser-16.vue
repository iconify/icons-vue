<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqaljb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kjqaljb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:browser-16" /></template>
