<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st9g-20gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st9g-20gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:line-height" /></template>
