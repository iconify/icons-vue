<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvhu8yb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvhu8yb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ads-off" /></template>
