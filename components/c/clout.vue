<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk-zyny4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mk-zyny4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clout" /></template>
