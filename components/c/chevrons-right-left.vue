<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qclgze96h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qclgze96h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevrons-right-left" /></template>
