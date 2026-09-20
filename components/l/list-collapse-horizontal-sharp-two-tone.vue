<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t361nh1vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t361nh1vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-collapse-horizontal-sharp-two-tone" /></template>
