<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9dzyiszx.css';
import '../../css/h/hfunc-u9d.css';
import '../../css/v/vm6ftdb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v9dzyiszx"/><path class="hfunc-u9d"/><path class="vm6ftdb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-x-20" /></template>
