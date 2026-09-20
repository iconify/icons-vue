<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkpht6big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkpht6big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-left-up-solid" /></template>
