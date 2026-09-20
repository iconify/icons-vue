<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so6r9ib0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so6r9ib0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:chatwoot" /></template>
