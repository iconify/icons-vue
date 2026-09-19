<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af5y71jug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="af5y71jug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ghost" /></template>
