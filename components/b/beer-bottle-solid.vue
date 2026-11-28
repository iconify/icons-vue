<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hot8poxda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hot8poxda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:beer-bottle-solid" /></template>
