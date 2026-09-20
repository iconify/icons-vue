<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oly8rvbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="oly8rvbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:box-f" /></template>
