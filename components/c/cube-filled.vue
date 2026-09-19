<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9a5m2bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9a5m2bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cube-filled" /></template>
