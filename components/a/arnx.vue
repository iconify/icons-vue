<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2j9mlb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a2j9mlb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:arnx" /></template>
