<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrdj_04qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdj_04qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:comment" /></template>
