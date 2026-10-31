<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npdco_cou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npdco_cou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-cane-gloss" /></template>
