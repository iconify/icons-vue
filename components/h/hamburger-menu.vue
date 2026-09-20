<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0elk-azn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k0elk-azn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hamburger-menu" /></template>
