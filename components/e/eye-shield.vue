<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz9ys0aib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fz9ys0aib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eye-shield" /></template>
