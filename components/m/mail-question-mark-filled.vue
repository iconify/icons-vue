<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foq2a6bdh.css';
import '../../css/m/mp780dcuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foq2a6bdh"/><path class="mp780dcuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-question-mark-filled" /></template>
