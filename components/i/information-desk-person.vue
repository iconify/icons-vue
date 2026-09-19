<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrz8nvb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nrz8nvb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:information-desk-person" /></template>
