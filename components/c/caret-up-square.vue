<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq55bsbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq55bsbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:caret-up-square" /></template>
