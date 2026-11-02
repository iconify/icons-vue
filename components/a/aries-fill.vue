<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acozjp_8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acozjp_8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aries-fill" /></template>
