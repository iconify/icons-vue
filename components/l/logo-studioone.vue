<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x70ytk24j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x70ytk24j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-studioone" /></template>
