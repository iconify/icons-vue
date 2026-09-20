<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8zze2brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8zze2brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-check" /></template>
