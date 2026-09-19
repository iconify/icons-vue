<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgl8xnb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zgl8xnb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-text-middle" /></template>
