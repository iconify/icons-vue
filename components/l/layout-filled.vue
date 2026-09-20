<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvlknyuzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvlknyuzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:layout-filled" /></template>
