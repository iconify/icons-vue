<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt1h73gnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt1h73gnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:horizontal-distribution-center" /></template>
