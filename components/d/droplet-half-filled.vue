<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb56hqbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb56hqbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-half-filled" /></template>
