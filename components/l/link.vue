<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvgjsjngl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvgjsjngl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:link" /></template>
