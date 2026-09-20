<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2bg46x2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a2bg46x2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:diamonds-symbol-solid" /></template>
