<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvw6yy-du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvw6yy-du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:garage" /></template>
