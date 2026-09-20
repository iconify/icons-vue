<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj3_hyblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj3_hyblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-scan-fill" /></template>
