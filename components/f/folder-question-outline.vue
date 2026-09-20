<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpq-ag9ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpq-ag9ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-question-outline" /></template>
