<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vor1jkb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vor1jkb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-down" /></template>
