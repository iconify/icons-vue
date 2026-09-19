<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fapcdg5-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fapcdg5-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:calendar" /></template>
