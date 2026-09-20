<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_gnyab1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_gnyab1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:code-2-filled" /></template>
