<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exin_vbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exin_vbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-down-line" /></template>
