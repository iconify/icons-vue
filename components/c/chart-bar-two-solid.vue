<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilrxzmlqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilrxzmlqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-bar-two-solid" /></template>
