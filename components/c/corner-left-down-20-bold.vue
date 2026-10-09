<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehv5ztb4q.css';
import '../../css/i/ijrr7tsvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ehv5ztb4q"/><path class="ijrr7tsvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-left-down-20-bold" /></template>
