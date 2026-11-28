<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im2a0lb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im2a0lb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cast-x" /></template>
