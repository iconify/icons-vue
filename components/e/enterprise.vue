<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iif_9hzvg.css';
import '../../css/k/klfo1ab7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iif_9hzvg"/><path class="klfo1ab7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:enterprise" /></template>
