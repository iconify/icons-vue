<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7tz73t3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e7tz73t3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:label-small-filled" /></template>
