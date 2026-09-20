<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n98cmlxqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n98cmlxqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-right-circle-solid" /></template>
