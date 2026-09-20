<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuvicbc1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuvicbc1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:building-2-line" /></template>
