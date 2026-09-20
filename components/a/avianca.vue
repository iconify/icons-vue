<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa0m7rgzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa0m7rgzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:avianca" /></template>
