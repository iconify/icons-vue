<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvyw8shky.css';
import '../../css/s/si38sl8xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvyw8shky"/><path class="si38sl8xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:church" /></template>
