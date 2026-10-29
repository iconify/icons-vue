<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iohplibxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iohplibxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:case-sensitive-solid" /></template>
