<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxj-05m9f.css';
import '../../css/w/wafsj8bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sxj-05m9f"/><path class="wafsj8bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electrolyser-48-bold" /></template>
