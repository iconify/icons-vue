<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrr1bhbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrr1bhbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fedex" /></template>
