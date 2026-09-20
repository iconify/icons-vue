<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjtoopd_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjtoopd_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cookie-line" /></template>
