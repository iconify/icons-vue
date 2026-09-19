<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzh31fbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vzh31fbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:gear-fill-12" /></template>
