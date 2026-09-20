<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xikpskncw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xikpskncw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:login6-filled" /></template>
