<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-k9vbclp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-k9vbclp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coins" /></template>
