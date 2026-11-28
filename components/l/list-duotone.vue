<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eux9rf7bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eux9rf7bu primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-duotone" /></template>
