<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0aqmrivn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0aqmrivn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hp" /></template>
