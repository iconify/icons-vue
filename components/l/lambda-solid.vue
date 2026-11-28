<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2tt4mbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2tt4mbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lambda-solid" /></template>
