<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9bd6331a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s9bd6331a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:crv" /></template>
