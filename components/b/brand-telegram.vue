<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaj8_bb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaj8_bb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-telegram" /></template>
