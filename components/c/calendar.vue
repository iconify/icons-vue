<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glf6v1jiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glf6v1jiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:calendar" /></template>
