<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf5uwnd5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf5uwnd5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:electronics-capacitor-bold" /></template>
