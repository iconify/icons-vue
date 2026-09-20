<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5x84ccwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k5x84ccwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:half-bright-ltr" /></template>
