<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl1m3woem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl1m3woem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:astral" /></template>
