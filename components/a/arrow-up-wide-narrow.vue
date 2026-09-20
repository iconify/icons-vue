<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkm2a9i0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkm2a9i0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-wide-narrow" /></template>
