<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axycgkb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axycgkb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:digg" /></template>
