<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jav-cm73x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jav-cm73x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:laptop-2" /></template>
