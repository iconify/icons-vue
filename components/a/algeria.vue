<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9omx9tno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9omx9tno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:algeria" /></template>
