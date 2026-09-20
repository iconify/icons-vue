<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spnly9btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spnly9btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-commit-horizontal" /></template>
