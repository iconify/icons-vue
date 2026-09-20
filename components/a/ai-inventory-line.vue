<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_cnb8bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_cnb8bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-inventory-line" /></template>
