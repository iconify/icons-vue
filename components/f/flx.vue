<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awmhj_7ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="awmhj_7ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:flx" /></template>
