<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u325fvbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u325fvbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:crop" /></template>
