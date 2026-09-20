<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coy96zbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coy96zbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:life-guard-tube-1" /></template>
