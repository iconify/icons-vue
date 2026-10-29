<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9sk2mszl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9sk2mszl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-left-right-solid" /></template>
