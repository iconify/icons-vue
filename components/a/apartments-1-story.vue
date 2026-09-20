<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acvxodb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="acvxodb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-1-story" /></template>
