<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhgco_s2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhgco_s2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:exclamation-triangle-solid" /></template>
