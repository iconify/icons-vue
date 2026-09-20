<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrmg1583g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrmg1583g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:application-braces" /></template>
