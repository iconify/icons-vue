<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9orhby8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="z9orhby8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:circle-up" /></template>
