<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pytu8sdic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pytu8sdic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:check-fill" /></template>
