<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyba1rbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kyba1rbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:convert-pdf-2-remix" /></template>
