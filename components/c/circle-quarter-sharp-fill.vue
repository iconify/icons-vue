<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhs2-lbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vhs2-lbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-quarter-sharp-fill" /></template>
