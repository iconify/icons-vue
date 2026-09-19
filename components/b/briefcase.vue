<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4vak2i9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="r4vak2i9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:briefcase" /></template>
