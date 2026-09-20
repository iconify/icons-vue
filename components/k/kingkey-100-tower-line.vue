<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykuz0ccec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykuz0ccec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:kingkey-100-tower-line" /></template>
