<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trikf9bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trikf9bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:corner-down-right" /></template>
