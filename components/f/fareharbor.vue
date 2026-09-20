<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd0hplddj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd0hplddj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fareharbor" /></template>
