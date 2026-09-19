<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek3i1rb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ek3i1rb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-fast" /></template>
