<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlsl_5b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlsl_5b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:adjust-alt" /></template>
