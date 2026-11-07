<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzn135foz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzn135foz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-outline" /></template>
