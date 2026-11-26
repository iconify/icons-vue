<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3_cbsr6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3_cbsr6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:columns-2-plus-right" /></template>
