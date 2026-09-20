<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmq4g3bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qmq4g3bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:lounger" /></template>
