<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loq8_m6rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="loq8_m6rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-left-small-outline" /></template>
