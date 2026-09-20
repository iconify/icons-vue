<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp3a3pb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bp3a3pb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:emergency-exit-solid" /></template>
