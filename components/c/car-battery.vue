<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcyrh0b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kcyrh0b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:car-battery" /></template>
