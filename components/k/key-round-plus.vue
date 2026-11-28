<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chob2xo_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chob2xo_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:key-round-plus" /></template>
