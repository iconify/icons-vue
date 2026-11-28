<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd03k58vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zd03k58vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-double-down-duotone" /></template>
