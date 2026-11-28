<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9w83dibl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9w83dibl primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-delay-duotone" /></template>
