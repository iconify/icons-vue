<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5j10n4ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5j10n4ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-right-outline" /></template>
