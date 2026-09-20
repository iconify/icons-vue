<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyndq2b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pyndq2b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:flashlight-remix" /></template>
