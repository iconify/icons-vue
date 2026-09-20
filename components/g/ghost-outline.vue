<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnhiwwybg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnhiwwybg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ghost-outline" /></template>
