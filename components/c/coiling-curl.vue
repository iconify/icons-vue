<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe9si9r_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oe9si9r_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coiling-curl" /></template>
