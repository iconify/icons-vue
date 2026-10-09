<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dibcbtkzz.css';
import '../../css/p/pjb032xjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dibcbtkzz"/><path class="pjb032xjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:award-48-bold" /></template>
