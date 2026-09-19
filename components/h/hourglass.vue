<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su6l7fbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="su6l7fbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hourglass" /></template>
