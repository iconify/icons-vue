<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haijt0bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="haijt0bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-text-justify-outline" /></template>
