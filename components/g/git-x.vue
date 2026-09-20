<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u75qp8b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u75qp8b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-x" /></template>
