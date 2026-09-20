<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r--_kryyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r--_kryyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:local-florist-outline" /></template>
