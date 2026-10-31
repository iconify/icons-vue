<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfvnjqbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfvnjqbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-arrow-left-gloss" /></template>
