<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi1okejsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi1okejsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-down-left-two-tone" /></template>
