<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhoje1s1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lhoje1s1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-up" /></template>
