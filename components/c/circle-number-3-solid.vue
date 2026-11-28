<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1atj4rea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1atj4rea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-number-3-solid" /></template>
