<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqe4zc3ni.css';
import '../../css/g/gjba8cbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqe4zc3ni"/><path class="gjba8cbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-plus-2-filled" /></template>
