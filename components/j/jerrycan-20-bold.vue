<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8_cvzaik.css';
import '../../css/y/yhfvti82b.css';
import '../../css/y/y6rvtrb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s8_cvzaik"/><path class="yhfvti82b"/><path class="y6rvtrb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jerrycan-20-bold" /></template>
