<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v378jubmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v378jubmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-c" /></template>
