<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cckzn0bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cckzn0bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-down-solid" /></template>
