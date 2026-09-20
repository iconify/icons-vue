<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl2g-q1_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl2g-q1_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:link-add" /></template>
