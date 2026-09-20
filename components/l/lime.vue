<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfe7j2bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfe7j2bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lime" /></template>
