<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py8pa3bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="py8pa3bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:arrow-right-up" /></template>
