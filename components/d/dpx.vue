<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1clhq6qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1clhq6qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dpx" /></template>
