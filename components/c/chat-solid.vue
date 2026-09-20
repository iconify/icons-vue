<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m793uqbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m793uqbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:chat-solid" /></template>
