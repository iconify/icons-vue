<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-vbiqblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-vbiqblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:forward-field" /></template>
