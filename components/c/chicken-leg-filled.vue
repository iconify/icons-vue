<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhso8hlxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhso8hlxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chicken-leg-filled" /></template>
