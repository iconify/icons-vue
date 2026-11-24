<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjs88jsib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yjs88jsib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flower-filled" /></template>
