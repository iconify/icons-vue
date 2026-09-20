<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf9aldbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gf9aldbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:fork-knife-flat" /></template>
