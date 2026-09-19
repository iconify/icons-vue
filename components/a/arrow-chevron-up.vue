<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h14yj99de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h14yj99de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-chevron-up" /></template>
