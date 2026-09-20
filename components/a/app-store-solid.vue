<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5724xuzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q5724xuzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:app-store-solid" /></template>
