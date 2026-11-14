<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpdql_bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpdql_bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-no-axes-column" /></template>
