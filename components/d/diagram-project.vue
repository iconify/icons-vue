<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7-mqmb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7-mqmb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-project" /></template>
