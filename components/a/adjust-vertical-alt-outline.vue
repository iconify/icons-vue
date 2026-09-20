<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flp26rb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="flp26rb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:adjust-vertical-alt-outline" /></template>
