<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uflelspsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uflelspsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-check-outline" /></template>
