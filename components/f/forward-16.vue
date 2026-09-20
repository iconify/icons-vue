<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws3c52ixo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ws3c52ixo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:forward-16" /></template>
