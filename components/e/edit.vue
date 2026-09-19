<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u01qd4b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u01qd4b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:edit" /></template>
