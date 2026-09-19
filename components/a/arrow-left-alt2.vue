<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1r1b3bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v1r1b3bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:arrow-left-alt2" /></template>
