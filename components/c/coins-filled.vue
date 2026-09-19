<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol0yy7b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol0yy7b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:coins-filled" /></template>
