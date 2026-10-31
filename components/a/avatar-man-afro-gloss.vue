<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0mt_8qgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0mt_8qgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-afro-gloss" /></template>
