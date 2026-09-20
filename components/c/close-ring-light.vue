<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfsh_ybmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfsh_ybmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:close-ring-light" /></template>
