<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnl2u8b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vnl2u8b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:give-star-remix" /></template>
