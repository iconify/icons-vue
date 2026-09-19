<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_5h90x4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_5h90x4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-europe-filled" /></template>
