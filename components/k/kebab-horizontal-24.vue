<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kss-o9_-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kss-o9_-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:kebab-horizontal-24" /></template>
