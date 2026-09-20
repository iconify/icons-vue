<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibr0sobfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibr0sobfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:chart-bar" /></template>
