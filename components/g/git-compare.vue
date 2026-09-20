<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkfh--blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkfh--blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-compare" /></template>
