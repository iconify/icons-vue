<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj80fbt_q.css';
import '../../css/t/t_1qkzbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj80fbt_q"/><path class="t_1qkzbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:ad-solid" /></template>
