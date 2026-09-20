<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p70zijb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p70zijb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lineageos" /></template>
