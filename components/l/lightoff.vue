<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0cdhsbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="g0cdhsbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lightoff" /></template>
