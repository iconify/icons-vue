<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-xmnxb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k-xmnxb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:crossing-tram-road" /></template>
