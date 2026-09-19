<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9z1fbc2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9z1fbc2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-ruler" /></template>
