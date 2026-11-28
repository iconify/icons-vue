<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-cd3abek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-cd3abek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lock-off-solid" /></template>
