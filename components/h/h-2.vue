<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxbq8bc8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxbq8bc8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:h-2" /></template>
