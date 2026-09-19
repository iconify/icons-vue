<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwibdw4bb.css';
import '../../css/t/to64u9f4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="to64u9f4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left-circle" /></template>
