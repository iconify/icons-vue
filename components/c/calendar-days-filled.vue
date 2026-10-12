<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-m4kzb8y.css';
import '../../css/g/gjba8cbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-m4kzb8y"/><path class="gjba8cbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-days-filled" /></template>
