<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prrawhb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prrawhb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:heart-add-line" /></template>
