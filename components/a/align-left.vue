<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfm2g-bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfm2g-bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-left" /></template>
