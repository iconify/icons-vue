<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi22qibhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi22qibhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-e-diamond-solid" /></template>
