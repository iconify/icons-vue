<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm1mhvr8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm1mhvr8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bed-bunk-solid" /></template>
