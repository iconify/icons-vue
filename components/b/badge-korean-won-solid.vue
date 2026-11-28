<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trs_dtk_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trs_dtk_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-korean-won-solid" /></template>
