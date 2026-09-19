<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_mtb3oij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_mtb3oij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bill" /></template>
