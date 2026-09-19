<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkk2jqbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkk2jqbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-down-arrow-circle" /></template>
