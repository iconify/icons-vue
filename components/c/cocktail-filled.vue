<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjmf1cc3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjmf1cc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cocktail-filled" /></template>
