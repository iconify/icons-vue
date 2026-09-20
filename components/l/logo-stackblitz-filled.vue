<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf2s_do7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rf2s_do7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-stackblitz-filled" /></template>
