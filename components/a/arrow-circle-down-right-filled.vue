<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7m7zsltm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7m7zsltm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-down-right-filled" /></template>
