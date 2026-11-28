<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2t86ck2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2t86ck2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clock-x" /></template>
