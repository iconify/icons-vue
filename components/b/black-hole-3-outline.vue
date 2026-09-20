<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocx9c_b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocx9c_b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:black-hole-3-outline" /></template>
