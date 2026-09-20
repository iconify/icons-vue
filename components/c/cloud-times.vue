<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3ink0bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3ink0bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-times" /></template>
