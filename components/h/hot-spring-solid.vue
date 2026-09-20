<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly34j431r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly34j431r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hot-spring-solid" /></template>
