<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr4flk_qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr4flk_qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:long-up-left" /></template>
