<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd-x80xmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd-x80xmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-down-outline" /></template>
