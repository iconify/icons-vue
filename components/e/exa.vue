<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au8fi6b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="au8fi6b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:exa" /></template>
