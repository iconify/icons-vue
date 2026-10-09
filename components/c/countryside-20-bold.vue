<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hseox7a5f.css';
import '../../css/r/rdbz-ccxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hseox7a5f"/><path class="rdbz-ccxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:countryside-20-bold" /></template>
