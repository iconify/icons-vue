<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3v_fcbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3v_fcbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fog-outline" /></template>
