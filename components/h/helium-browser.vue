<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzffiib9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzffiib9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:helium-browser" /></template>
