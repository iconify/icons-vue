<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8z63cb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q8z63cb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:diagonal-triangle-arrow-2-remix" /></template>
