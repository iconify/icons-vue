<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/losqoabyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="losqoabyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cards-heart" /></template>
