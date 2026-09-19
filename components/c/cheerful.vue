<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd-hzyb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bd-hzyb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cheerful" /></template>
