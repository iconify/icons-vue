<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hot9fjbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hot9fjbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:close-lg" /></template>
