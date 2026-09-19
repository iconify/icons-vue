<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej3np33fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ej3np33fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jeweled-chalice" /></template>
