<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c17c66b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c17c66b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:aerial-platter-lift" /></template>
