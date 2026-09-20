<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi4m82f8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi4m82f8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:dhall" /></template>
