<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_bvvacrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":24};
const content = `<path class="w_bvvacrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:favorite" /></template>
