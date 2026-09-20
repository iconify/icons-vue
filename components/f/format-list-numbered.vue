<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2lls-ime.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2lls-ime"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-list-numbered" /></template>
