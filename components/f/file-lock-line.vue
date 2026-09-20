<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8lpyt6bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8lpyt6bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-lock-line" /></template>
