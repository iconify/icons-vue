<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqlqtrkhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqlqtrkhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:coffee-plus" /></template>
