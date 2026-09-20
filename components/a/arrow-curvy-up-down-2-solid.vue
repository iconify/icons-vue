<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj_4nmmiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oj_4nmmiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-curvy-up-down-2-solid" /></template>
