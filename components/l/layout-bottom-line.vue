<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzqk00u5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqk00u5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-bottom-line" /></template>
