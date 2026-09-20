<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1nmgt7zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1nmgt7zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-forbid-fill" /></template>
