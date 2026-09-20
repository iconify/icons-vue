<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6xqstv_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6xqstv_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-3-fill" /></template>
