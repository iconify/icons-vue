<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lep7-fbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lep7-fbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-check-solid" /></template>
