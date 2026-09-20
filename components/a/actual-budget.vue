<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzhztek1e.css';
import '../../css/a/a1lsv6bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gzhztek1e"/><path class="a1lsv6bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:actual-budget" /></template>
