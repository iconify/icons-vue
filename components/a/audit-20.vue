<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bodkpqb0q.css';
import '../../css/p/p3ccqddap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bodkpqb0q"/><path class="p3ccqddap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:audit-20" /></template>
