<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcdz5x3sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcdz5x3sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ana" /></template>
