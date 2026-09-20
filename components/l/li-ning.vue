<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcho2thtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcho2thtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:li-ning" /></template>
