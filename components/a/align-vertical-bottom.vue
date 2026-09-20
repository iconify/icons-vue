<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic5m1gpux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ic5m1gpux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:align-vertical-bottom" /></template>
