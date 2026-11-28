<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynwb_uh6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynwb_uh6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:list-x" /></template>
