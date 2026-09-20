<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4la0lb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4la0lb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-ember" /></template>
