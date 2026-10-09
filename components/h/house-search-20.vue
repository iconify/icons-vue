<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7juawdew.css';
import '../../css/o/o5q8omqss.css';
import '../../css/l/l72lv6f7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7juawdew"/><path class="o5q8omqss"/><path class="l72lv6f7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-search-20" /></template>
