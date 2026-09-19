<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw3l-abfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aw3l-abfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gibbet" /></template>
