<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d49j50b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d49j50b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lightning-cable-outline" /></template>
