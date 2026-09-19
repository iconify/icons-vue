<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra33s9tks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra33s9tks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:firebase" /></template>
