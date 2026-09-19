<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmj2tv-_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lmj2tv-_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-cross-square-small" /></template>
