<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u90m3kb-a.css';
import '../../css/p/pzmtr-buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u90m3kb-a"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-down-outline" /></template>
