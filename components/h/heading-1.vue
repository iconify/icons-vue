<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfcvlzbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfcvlzbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-1" /></template>
