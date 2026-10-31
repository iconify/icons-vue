<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqaj_ob-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqaj_ob-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:airplay-round" /></template>
