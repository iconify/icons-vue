<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbcnw6b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gbcnw6b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-pause" /></template>
