<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9-jvcgtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9-jvcgtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical-waves-solid" /></template>
