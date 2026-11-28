<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_s8ribpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_s8ribpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:droplet-x" /></template>
