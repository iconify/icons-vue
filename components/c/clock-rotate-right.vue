<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/um27ogbzd.css';
import '../../css/o/ol6ywj3wc.css';
import '../../css/k/k0jum4blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="um27ogbzd"/><path class="ol6ywj3wc"/><path class="k0jum4blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:clock-rotate-right" /></template>
