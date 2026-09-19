<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m82ucs_8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m82ucs_8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-left-two" /></template>
