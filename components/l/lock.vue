<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f964tccdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="f964tccdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:lock" /></template>
