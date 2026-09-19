<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr7n_jb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr7n_jb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:binocular" /></template>
