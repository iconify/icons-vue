<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1k5aabax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1k5aabax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-plane-take-off" /></template>
