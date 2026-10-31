<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ot12pbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ot12pbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-down-round" /></template>
