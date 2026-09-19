<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn-h4zb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xn-h4zb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bar-stool" /></template>
