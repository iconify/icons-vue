<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu766whky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu766whky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:git-pull-request-arrow" /></template>
