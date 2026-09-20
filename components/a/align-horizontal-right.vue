<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a93huobqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a93huobqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:align-horizontal-right" /></template>
