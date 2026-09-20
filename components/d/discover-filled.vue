<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rddvsb4-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rddvsb4-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:discover-filled" /></template>
