<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_1qmdbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_1qmdbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:archive-x" /></template>
