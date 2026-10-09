<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0zh2bb8f.css';
import '../../css/t/tnm3gqoro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s0zh2bb8f"/><path class="tnm3gqoro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:files-20" /></template>
