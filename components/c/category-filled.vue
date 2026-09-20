<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv7_whsec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv7_whsec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:category-filled" /></template>
