<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjmsq1nep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjmsq1nep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-down-arrow-square" /></template>
