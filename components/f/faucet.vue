<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usipjj-vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usipjj-vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:faucet" /></template>
