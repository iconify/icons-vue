<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuemf_bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuemf_bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashed-line-01" /></template>
