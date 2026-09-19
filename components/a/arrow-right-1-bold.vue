<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/par19ibbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="par19ibbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-1-bold" /></template>
