<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez251fscv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ez251fscv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:google-drive-solid" /></template>
