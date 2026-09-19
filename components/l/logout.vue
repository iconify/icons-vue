<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1p1vubmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e1p1vubmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:logout" /></template>
