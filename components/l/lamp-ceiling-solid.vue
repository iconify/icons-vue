<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn7n91bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn7n91bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lamp-ceiling-solid" /></template>
