<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o59f1m2si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="o59f1m2si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:archery" /></template>
