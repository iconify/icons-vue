<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/legbnrz8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="legbnrz8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bus-x" /></template>
