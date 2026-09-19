<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wookawbbo.css';
import '../../css/p/p8dgzzb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wookawbbo"/><path class="p8dgzzb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hospital" /></template>
