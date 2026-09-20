<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvuoydryf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvuoydryf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bollard" /></template>
