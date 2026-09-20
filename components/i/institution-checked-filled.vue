<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yakv6sbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yakv6sbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:institution-checked-filled" /></template>
