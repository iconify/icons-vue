<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kak5-8b1v.css';
import '../../css/y/ylye7u88m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kak5-8b1v"/><path class="ylye7u88m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:line-height-20" /></template>
