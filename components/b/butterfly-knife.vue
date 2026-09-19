<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/extb2-b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="extb2-b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:butterfly-knife" /></template>
