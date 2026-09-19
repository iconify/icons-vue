<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2fp4nqfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="u2fp4nqfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-tears" /></template>
