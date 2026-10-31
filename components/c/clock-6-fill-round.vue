<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-nt2u-ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-nt2u-ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-6-fill-round" /></template>
