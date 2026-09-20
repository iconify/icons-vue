<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9fl78bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9fl78bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-dolby-digital" /></template>
