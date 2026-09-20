<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x23z73bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x23z73bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:doc-medical" /></template>
