<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj73phbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj73phbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:letter-underline-outline" /></template>
