<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yinj-bcbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yinj-bcbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-foursquare" /></template>
