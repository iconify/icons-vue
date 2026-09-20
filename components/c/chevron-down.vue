<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca3d_pk8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca3d_pk8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:chevron-down" /></template>
