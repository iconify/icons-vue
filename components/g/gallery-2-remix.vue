<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1pqg6vdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c1pqg6vdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:gallery-2-remix" /></template>
