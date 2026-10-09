<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umeximbue.css';
import '../../css/z/zyqw81bux.css';
import '../../css/r/r98z67v2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="umeximbue"/><path class="zyqw81bux"/><path class="r98z67v2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lighthouse-20-bold" /></template>
