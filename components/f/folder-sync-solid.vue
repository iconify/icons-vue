<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqs8dcnai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqs8dcnai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-sync-solid" /></template>
