<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su_mzgvzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="su_mzgvzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:industry-innovation-and-infrastructure-remix" /></template>
