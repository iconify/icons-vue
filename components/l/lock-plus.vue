<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4t2qqsmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4t2qqsmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lock-plus" /></template>
