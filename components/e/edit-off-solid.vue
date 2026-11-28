<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys95-wbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys95-wbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:edit-off-solid" /></template>
