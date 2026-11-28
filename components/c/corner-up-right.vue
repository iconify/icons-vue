<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_6_n2brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_6_n2brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:corner-up-right" /></template>
