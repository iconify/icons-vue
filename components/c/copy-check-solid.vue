<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qets41bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qets41bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:copy-check-solid" /></template>
