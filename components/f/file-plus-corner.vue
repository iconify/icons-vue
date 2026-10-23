<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poj89ybss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poj89ybss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-plus-corner" /></template>
