<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j326ocbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j326ocbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:briefcase" /></template>
