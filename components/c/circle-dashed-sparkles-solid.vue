<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh_edkpcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh_edkpcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-dashed-sparkles-solid" /></template>
