<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eam_kubxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eam_kubxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:flag-solid" /></template>
