<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3rkm0boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3rkm0boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:candy" /></template>
