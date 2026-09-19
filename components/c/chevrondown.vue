<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9z807bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="m9z807bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:chevrondown" /></template>
