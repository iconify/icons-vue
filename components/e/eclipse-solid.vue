<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw7a4lb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw7a4lb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:eclipse-solid" /></template>
