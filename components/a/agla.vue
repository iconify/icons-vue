<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrm345inh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zrm345inh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:agla" /></template>
