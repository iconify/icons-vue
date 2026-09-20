<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scjro9brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scjro9brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:image-24" /></template>
