<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2w7l9b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2w7l9b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-donate-heart" /></template>
