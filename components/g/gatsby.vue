<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjz1-db4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjz1-db4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:gatsby" /></template>
