<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9qc58bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9qc58bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:document-layout-left" /></template>
