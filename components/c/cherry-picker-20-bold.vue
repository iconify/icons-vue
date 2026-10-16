<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k__-9jb3z.css';
import '../../css/e/eflquttdn.css';
import '../../css/x/x2yw4q15w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k__-9jb3z"/><path class="eflquttdn"/><path class="x2yw4q15w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cherry-picker-20-bold" /></template>
