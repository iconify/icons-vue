<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thqbk35ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thqbk35ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:heart" /></template>
