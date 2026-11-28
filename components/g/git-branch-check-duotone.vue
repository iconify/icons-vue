<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omjlb3bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omjlb3bip primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-branch-check-duotone" /></template>
