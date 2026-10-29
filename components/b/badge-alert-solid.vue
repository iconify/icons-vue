<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckyds_bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckyds_bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-alert-solid" /></template>
