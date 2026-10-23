<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la3g_rb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la3g_rb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-up-dash" /></template>
