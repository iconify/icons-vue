<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0mtshrrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="u0mtshrrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:battery-three-quarters" /></template>
