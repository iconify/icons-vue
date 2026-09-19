<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-uzgj8_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-uzgj8_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:linked-rings" /></template>
