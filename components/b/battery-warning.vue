<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab65ey4uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab65ey4uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:battery-warning" /></template>
