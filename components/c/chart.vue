<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9_xqx6dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9_xqx6dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chart" /></template>
