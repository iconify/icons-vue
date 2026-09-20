<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nycqncbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nycqncbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:copyright-solid" /></template>
