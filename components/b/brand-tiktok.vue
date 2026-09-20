<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8t_v446c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8t_v446c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-tiktok" /></template>
