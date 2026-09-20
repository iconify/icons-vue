<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cns968kiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cns968kiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:generalmotors" /></template>
