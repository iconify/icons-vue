<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvec2bb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvec2bb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hair-dryer" /></template>
