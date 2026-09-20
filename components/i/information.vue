<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aik-f7fra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aik-f7fra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:information" /></template>
