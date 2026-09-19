<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6q1ptbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v6q1ptbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:heart-dislike-circle-sharp" /></template>
