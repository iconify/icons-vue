<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_6i7yibv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_6i7yibv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:cafeteria" /></template>
