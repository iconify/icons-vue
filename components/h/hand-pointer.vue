<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usa9yzfgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usa9yzfgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:hand-pointer" /></template>
