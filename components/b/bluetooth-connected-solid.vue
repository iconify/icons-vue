<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiwn5ycja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiwn5ycja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bluetooth-connected-solid" /></template>
