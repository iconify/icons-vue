<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqb6uo3um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqb6uo3um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-check-round" /></template>
