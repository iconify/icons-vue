<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbx9m__qq.css';
import '../../css/b/bj40tef2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tbx9m__qq"/><path class="bj40tef2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-down-right-20" /></template>
