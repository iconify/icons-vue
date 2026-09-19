<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydt4-bcup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ydt4-bcup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crossroad" /></template>
