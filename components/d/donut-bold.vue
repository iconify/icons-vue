<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6uklktlq.css';
import '../../css/k/kk94-14if.css';
import '../../css/x/xitnz62wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6uklktlq"/><path class="kk94-14if"/><path clip-rule="evenodd" class="xitnz62wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:donut-bold" /></template>
