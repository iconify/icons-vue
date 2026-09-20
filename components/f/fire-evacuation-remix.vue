<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl0omacja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bl0omacja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fire-evacuation-remix" /></template>
