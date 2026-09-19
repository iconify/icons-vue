<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu87s-b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu87s-b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bus" /></template>
