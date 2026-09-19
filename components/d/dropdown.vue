<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rup5qzhbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":616,"height":614};
const content = `<path class="rup5qzhbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:dropdown" /></template>
