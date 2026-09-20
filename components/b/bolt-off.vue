<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe-ssol4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe-ssol4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bolt-off" /></template>
