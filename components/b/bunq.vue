<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbm-3_bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbm-3_bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bunq" /></template>
