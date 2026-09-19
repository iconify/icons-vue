<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puo04wbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="puo04wbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:check" /></template>
