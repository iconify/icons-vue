<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq56q7baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq56q7baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:four-square-solid" /></template>
