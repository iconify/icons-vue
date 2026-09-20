<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3bc0lb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="q3bc0lb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-downward" /></template>
