<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr41nybew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr41nybew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:hashcat" /></template>
