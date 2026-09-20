<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quymce01g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="quymce01g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:exa" /></template>
