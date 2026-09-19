<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp2zgn6iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pp2zgn6iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:alarm-fill" /></template>
