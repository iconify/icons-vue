<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3cscxblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3cscxblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:home-light" /></template>
