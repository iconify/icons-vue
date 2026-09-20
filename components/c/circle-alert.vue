<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9l8db71u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9l8db71u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-alert" /></template>
