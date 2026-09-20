<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iepnh6q-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iepnh6q-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:car" /></template>
