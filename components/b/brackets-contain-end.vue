<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzgszvbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzgszvbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brackets-contain-end" /></template>
