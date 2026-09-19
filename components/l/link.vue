<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trsn-3cdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trsn-3cdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:link" /></template>
