<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pffl33b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pffl33b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:filter-3-fill" /></template>
