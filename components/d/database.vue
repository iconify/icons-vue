<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwrg4jbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vwrg4jbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:database" /></template>
