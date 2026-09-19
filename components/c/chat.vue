<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2zey2evm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r2zey2evm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chat" /></template>
