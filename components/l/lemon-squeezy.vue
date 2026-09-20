<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuo09szyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":28};
const content = `<path clip-rule="evenodd" class="cuo09szyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lemon-squeezy" /></template>
