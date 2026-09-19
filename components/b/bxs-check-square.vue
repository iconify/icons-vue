<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brb3lt_gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brb3lt_gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-check-square" /></template>
