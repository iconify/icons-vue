<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqq8rqbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqq8rqbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:electricity-filled" /></template>
