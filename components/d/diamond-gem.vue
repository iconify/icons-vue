<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qab_zlbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qab_zlbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:diamond-gem" /></template>
