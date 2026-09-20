<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkhi61bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkhi61bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:headspace" /></template>
