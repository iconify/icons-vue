<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yght1vonp.css';
import '../../css/s/s1qzz4b8q.css';
import '../../css/f/fj5yv9btn.css';
import '../../css/o/o9z99rbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yght1vonp"/><path class="s1qzz4b8q"/><path class="fj5yv9btn"/><path class="o9z99rbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-tank-20" /></template>
