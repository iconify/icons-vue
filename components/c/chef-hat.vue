<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgw8fbnzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgw8fbnzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chef-hat" /></template>
