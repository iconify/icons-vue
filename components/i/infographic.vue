<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1m3t8g2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g1m3t8g2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:infographic" /></template>
