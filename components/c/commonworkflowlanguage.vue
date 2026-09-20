<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgxpadckc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgxpadckc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:commonworkflowlanguage" /></template>
