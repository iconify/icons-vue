<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovbrx1qav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ovbrx1qav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bush" /></template>
