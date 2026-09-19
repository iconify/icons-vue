<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi4gs-b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qi4gs-b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:forward" /></template>
