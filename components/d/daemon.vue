<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq86uabao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq86uabao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:daemon" /></template>
