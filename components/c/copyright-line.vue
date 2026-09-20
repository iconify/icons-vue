<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-68ozbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-68ozbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:copyright-line" /></template>
