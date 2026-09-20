<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhdaigbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhdaigbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:code4-filled" /></template>
