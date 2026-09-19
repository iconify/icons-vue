<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx5-5bc-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gx5-5bc-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:diplodocus" /></template>
