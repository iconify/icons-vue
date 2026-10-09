<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htetqt6dv.css';
import '../../css/z/zh18k_bxi.css';
import '../../css/h/heyzer6mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="htetqt6dv"/><path class="zh18k_bxi"/><path class="heyzer6mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:film-48" /></template>
