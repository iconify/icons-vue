<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6rs07cfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6rs07cfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:add-circle-filled" /></template>
