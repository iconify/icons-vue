<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw0-izbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lw0-izbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:briefcase-cross" /></template>
