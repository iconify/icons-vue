<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otamqwb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="otamqwb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:error" /></template>
