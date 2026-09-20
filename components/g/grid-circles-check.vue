<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c66wt6iaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c66wt6iaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-check" /></template>
