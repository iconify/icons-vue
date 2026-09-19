<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awmipqbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awmipqbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-dice-6" /></template>
