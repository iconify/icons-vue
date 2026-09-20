<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwtqj9_vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwtqj9_vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-block" /></template>
