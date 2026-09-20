<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey8c2qbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey8c2qbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-stocktwits" /></template>
