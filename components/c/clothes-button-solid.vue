<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkacrgb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkacrgb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clothes-button-solid" /></template>
