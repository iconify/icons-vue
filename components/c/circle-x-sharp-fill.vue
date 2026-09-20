<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q19gspbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q19gspbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-x-sharp-fill" /></template>
