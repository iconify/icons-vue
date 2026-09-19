<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1lbyxb3k.css';
import '../../css/p/p-t5oux0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="x1lbyxb3k"/><path class="p-t5oux0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:copy-outline" /></template>
