<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axg085ttp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axg085ttp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budget-board-dark" /></template>
