<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_3p-cbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_3p-cbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flexible-star" /></template>
