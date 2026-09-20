<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3fac04nz.css';
import '../../css/h/hj-hvqmvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3fac04nz"/><path class="hj-hvqmvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:combine-line" /></template>
