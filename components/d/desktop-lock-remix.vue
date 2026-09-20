<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl-ffz72e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gl-ffz72e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:desktop-lock-remix" /></template>
