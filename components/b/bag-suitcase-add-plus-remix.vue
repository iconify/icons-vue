<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olsu_qbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="olsu_qbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bag-suitcase-add-plus-remix" /></template>
