<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og69_74sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og69_74sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book3-filled" /></template>
