<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhfrptb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhfrptb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bell-off" /></template>
