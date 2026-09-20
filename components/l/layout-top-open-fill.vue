<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsl067b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsl067b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-top-open-fill" /></template>
