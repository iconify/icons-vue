<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5r1m1pkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5r1m1pkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:archive-out" /></template>
