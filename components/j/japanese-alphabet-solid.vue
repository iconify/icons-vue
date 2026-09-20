<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1ap4nbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e1ap4nbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:japanese-alphabet-solid" /></template>
