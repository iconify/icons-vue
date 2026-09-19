<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttw1qx63j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ttw1qx63j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:car-battery" /></template>
