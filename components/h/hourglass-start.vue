<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz6astb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="hz6astb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hourglass-start" /></template>
