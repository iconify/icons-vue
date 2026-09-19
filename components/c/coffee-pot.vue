<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv3g54blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv3g54blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coffee-pot" /></template>
