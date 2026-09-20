<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg28xqbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tg28xqbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:close" /></template>
