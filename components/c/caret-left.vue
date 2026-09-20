<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h--u52bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h--u52bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:caret-left" /></template>
