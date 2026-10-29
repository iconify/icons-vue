<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oalh-698v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oalh-698v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-left-to-line-solid" /></template>
