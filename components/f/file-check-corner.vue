<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs9r7ablm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9r7ablm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-check-corner" /></template>
