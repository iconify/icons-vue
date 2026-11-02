<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r64kgzu8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r64kgzu8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-bottom-open-line" /></template>
