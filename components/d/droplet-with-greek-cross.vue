<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnaizab9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fnaizab9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-with-greek-cross" /></template>
