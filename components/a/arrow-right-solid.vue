<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cme-xj5sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cme-xj5sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-right-solid" /></template>
