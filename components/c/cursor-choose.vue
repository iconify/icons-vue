<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv9ll_bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv9ll_bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cursor-choose" /></template>
