<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfkl0zb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sfkl0zb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:goblet-full" /></template>
