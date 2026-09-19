<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0-0whfbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0-0whfbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:info" /></template>
