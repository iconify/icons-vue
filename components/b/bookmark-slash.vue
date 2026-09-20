<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdtlezb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdtlezb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bookmark-slash" /></template>
