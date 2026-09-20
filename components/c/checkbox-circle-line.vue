<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx4n7nbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx4n7nbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:checkbox-circle-line" /></template>
