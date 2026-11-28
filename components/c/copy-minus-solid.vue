<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7xpe8roh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7xpe8roh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:copy-minus-solid" /></template>
