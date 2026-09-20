<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg7u55lgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg7u55lgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folders" /></template>
