<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gah9kwbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gah9kwbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desalination-20" /></template>
