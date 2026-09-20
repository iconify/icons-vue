<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyjzgacii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyjzgacii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dash0" /></template>
