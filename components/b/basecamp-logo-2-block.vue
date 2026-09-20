<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy3jago4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oy3jago4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:basecamp-logo-2-block" /></template>
