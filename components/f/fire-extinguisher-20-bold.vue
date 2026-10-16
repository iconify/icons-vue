<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr0xwjb7c.css';
import '../../css/p/pv2lfsb0a.css';
import '../../css/v/v09rlcbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lr0xwjb7c"/><path class="pv2lfsb0a"/><path class="v09rlcbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-extinguisher-20-bold" /></template>
