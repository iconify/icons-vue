<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd98jnfaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kd98jnfaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-right-to-line" /></template>
