<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-r2anv0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m-r2anv0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:close" /></template>
