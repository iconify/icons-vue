<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4p_ytb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u4p_ytb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:agent-filled" /></template>
