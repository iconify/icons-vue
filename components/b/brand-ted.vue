<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on5qrlw_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on5qrlw_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-ted" /></template>
