<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rigzz57ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rigzz57ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:closet2" /></template>
