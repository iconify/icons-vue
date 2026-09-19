<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4spwt7oj.css';
import '../../css/u/utvngb1dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4spwt7oj"/><path class="utvngb1dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:content-deleted" /></template>
