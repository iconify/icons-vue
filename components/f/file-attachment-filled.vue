<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h29s4bc8i.css';
import '../../css/m/mb5862dny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h29s4bc8i"/><path class="mb5862dny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-attachment-filled" /></template>
