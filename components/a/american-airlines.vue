<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_jtu1w5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_jtu1w5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:american-airlines" /></template>
