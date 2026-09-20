<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7bpfinmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t7bpfinmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:landscape-2-solid" /></template>
