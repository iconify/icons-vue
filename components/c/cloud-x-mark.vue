<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxna43buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxna43buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-x-mark" /></template>
