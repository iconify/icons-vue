<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1_2z9bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="a1_2z9bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hate" /></template>
