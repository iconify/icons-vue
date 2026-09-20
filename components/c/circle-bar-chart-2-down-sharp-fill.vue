<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anrqqjrjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="anrqqjrjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-2-down-sharp-fill" /></template>
