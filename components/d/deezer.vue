<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_t-wqbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6.5};
const content = `<path class="u_t-wqbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:deezer" /></template>
