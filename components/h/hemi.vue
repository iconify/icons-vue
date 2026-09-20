<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb44_vbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb44_vbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hemi" /></template>
