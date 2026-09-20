<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8vo07bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8vo07bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bell-plus" /></template>
