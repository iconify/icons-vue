<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvpxvsbif.css';
import '../../css/x/xph283bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qvpxvsbif"/><path class="xph283bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leaf-20-bold" /></template>
