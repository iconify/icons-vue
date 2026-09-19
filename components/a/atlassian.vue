<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm55zv6ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sm55zv6ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:atlassian" /></template>
