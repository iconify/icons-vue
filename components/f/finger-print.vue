<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_0an4c0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_0an4c0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:finger-print" /></template>
