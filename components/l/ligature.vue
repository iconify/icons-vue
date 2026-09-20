<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-7b34bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-7b34bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:ligature" /></template>
