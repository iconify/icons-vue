<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6v9hcbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b6v9hcbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calendar-note-remix" /></template>
