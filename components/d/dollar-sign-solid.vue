<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg44-slrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg44-slrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:dollar-sign-solid" /></template>
