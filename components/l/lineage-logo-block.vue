<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxl1wqb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxl1wqb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lineage-logo-block" /></template>
