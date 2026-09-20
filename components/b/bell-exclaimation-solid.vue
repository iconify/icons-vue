<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsvjd8bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsvjd8bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bell-exclaimation-solid" /></template>
