<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilv9ww7ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ilv9ww7ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:computer-outline" /></template>
