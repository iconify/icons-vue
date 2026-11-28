<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr69ofbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr69ofbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fast-forward" /></template>
