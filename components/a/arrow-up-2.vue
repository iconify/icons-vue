<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq302ibrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jq302ibrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-2" /></template>
