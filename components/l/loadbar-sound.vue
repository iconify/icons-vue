<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn4baw61j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn4baw61j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:loadbar-sound" /></template>
