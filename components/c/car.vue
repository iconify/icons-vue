<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6ubm4bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="v6ubm4bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:car" /></template>
