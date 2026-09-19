<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_o80v9iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="r_o80v9iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:external-link" /></template>
