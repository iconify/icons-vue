<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2514ubjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="y2514ubjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:copyright" /></template>
