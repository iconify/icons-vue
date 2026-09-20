<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0sg_1bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0sg_1bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-sort" /></template>
