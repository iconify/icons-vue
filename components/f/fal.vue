<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfbm-5bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pfbm-5bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fal" /></template>
