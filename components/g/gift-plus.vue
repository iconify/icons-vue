<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5k312trr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5k312trr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:gift-plus" /></template>
