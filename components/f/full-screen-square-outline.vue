<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqbv1hb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqbv1hb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:full-screen-square-outline" /></template>
