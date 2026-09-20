<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrevshc3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrevshc3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:corner-down-left" /></template>
