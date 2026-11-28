<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coo41t5hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coo41t5hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dollar-circle-solid" /></template>
