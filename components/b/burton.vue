<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh7o_5bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh7o_5bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:burton" /></template>
