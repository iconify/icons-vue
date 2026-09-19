<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu4jmcblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu4jmcblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:briefcase-alt-filled" /></template>
