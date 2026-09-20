<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvsjprm_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvsjprm_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-right" /></template>
