<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt3xv6jin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt3xv6jin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clock-9" /></template>
