<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh98s4b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh98s4b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chevron-circle-down" /></template>
