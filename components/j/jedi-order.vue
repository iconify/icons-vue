<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcrx_c8wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dcrx_c8wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:jedi-order" /></template>
