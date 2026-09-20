<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq8_dqbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq8_dqbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:argo" /></template>
