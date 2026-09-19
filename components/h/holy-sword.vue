<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3t3o83lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k3t3o83lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:holy-sword" /></template>
