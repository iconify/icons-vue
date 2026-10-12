<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k0bqss54y.css';
import '../../css/k/khng8rbjh.css';
import '../../css/q/qjxwpdimh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k0bqss54y"/><path class="khng8rbjh"/><path class="qjxwpdimh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dessert-duotone" /></template>
