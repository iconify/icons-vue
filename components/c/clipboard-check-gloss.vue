<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwu9w-bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwu9w-bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-check-gloss" /></template>
