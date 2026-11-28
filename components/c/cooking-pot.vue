<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5ibo_bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ibo_bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cooking-pot" /></template>
