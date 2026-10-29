<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyqrm_auc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyqrm_auc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dollar-sign-solid" /></template>
