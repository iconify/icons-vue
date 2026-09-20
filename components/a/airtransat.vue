<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb6yg9b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb6yg9b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:airtransat" /></template>
