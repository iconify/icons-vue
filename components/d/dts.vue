<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhdr_7b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhdr_7b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dts" /></template>
