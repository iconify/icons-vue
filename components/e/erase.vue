<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayhgwxblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ayhgwxblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:erase" /></template>
