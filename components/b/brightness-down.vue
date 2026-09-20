<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvjt4o66g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="nvjt4o66g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:brightness-down" /></template>
