<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnxvq404g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnxvq404g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fine-tune" /></template>
