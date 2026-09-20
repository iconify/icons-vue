<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw1itqbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw1itqbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bolt-lightning" /></template>
