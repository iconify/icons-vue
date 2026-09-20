<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk9pi6bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk9pi6bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-tapd" /></template>
