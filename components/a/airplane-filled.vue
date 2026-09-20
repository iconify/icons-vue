<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmw_nynco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmw_nynco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:airplane-filled" /></template>
