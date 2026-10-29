<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l25a_acmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l25a_acmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:info-circle-solid" /></template>
