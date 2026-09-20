<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcv07kbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gcv07kbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:airport-security-solid" /></template>
