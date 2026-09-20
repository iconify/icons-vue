<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lww32bc-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lww32bc-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bus" /></template>
