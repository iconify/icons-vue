<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouxk6zp2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ouxk6zp2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-5-circle-fill" /></template>
