<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfzmnvd-w.css';
import '../../css/k/kz8f7vbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lfzmnvd-w"/><path class="kz8f7vbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-20" /></template>
