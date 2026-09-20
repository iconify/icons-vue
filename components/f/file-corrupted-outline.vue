<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odgrk3hlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odgrk3hlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-corrupted-outline" /></template>
