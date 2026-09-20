<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db-6pbbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db-6pbbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:lighthouse" /></template>
