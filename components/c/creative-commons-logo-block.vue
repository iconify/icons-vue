<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd49lac2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qd49lac2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:creative-commons-logo-block" /></template>
