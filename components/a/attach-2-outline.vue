<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5crthepf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5crthepf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:attach-2-outline" /></template>
