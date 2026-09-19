<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx_pg9buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx_pg9buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:battery-0" /></template>
