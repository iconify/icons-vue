<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etj_qccda.css';
import '../../css/x/xz53smi8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etj_qccda"/><path class="xz53smi8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:book-content" /></template>
