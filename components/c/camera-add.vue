<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7h7y4b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="u7h7y4b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:camera-add" /></template>
