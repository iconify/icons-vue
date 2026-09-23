<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awsq1zbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="awsq1zbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-2-sharp-fill" /></template>
