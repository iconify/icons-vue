<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2p4y856r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k2p4y856r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:git" /></template>
