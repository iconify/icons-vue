<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he_ivqbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="he_ivqbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:facebook" /></template>
