<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j81z2yx1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j81z2yx1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-50" /></template>
