<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4kosrbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4kosrbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-tapd-filled" /></template>
