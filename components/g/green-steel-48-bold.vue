<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs1xeldxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hs1xeldxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-steel-48-bold" /></template>
