<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_0kzp__o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_0kzp__o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alphabet-chinese" /></template>
