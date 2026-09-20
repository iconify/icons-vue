<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc9ac_byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc9ac_byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axis-z-arrow-lock" /></template>
