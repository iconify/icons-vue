<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_021jbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_021jbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-fill-round" /></template>
