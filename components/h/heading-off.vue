<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btrsm-kpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btrsm-kpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heading-off" /></template>
