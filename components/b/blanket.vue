<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z04v279_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z04v279_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:blanket" /></template>
