<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjdv2dp9t.css';
import '../../css/s/sla-3ib_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yjdv2dp9t"/><path class="sla-3ib_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bear-20-bold" /></template>
