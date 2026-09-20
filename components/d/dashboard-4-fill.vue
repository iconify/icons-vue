<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxzxubb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxzxubb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-4-fill" /></template>
