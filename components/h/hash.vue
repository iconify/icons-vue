<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdu_fnb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdu_fnb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hash" /></template>
