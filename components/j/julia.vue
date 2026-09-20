<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcahgwb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcahgwb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:julia" /></template>
