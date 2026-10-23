<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1s14pnwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1s14pnwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:clipboard-list" /></template>
