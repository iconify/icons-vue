<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk8o22bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk8o22bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:currency-yuan-bubble-bold" /></template>
