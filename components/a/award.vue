<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbikvqbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="fbikvqbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:award" /></template>
