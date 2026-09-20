<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhq6-qa5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nhq6-qa5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:embassy" /></template>
