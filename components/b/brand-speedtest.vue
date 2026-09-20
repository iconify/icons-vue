<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le1jd7b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le1jd7b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-speedtest" /></template>
