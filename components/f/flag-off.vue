<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gorzl_bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gorzl_bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-off" /></template>
