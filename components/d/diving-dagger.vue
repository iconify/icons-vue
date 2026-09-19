<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we64jwbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="we64jwbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:diving-dagger" /></template>
