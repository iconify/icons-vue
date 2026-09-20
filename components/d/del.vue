<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwrhr7bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwrhr7bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:del" /></template>
