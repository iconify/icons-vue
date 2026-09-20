<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zni5_hulp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zni5_hulp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:house-chimney-bold" /></template>
