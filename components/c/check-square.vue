<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7ux82p4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7ux82p4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:check-square" /></template>
