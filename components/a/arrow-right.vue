<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmoeigbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmoeigbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-right" /></template>
