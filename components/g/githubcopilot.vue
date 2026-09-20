<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytk4757ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytk4757ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:githubcopilot" /></template>
