<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-8yvxbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v-8yvxbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:generic-scan" /></template>
