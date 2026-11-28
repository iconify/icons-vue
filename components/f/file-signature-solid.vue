<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlkubj91s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlkubj91s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-signature-solid" /></template>
