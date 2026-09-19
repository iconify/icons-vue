<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mepqtl5jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mepqtl5jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:horned-helm" /></template>
