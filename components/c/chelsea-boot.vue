<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdum019nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdum019nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chelsea-boot" /></template>
