<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uclis5b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uclis5b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:cardiology" /></template>
