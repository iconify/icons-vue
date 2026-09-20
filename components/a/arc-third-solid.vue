<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjktqzbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjktqzbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arc-third-solid" /></template>
