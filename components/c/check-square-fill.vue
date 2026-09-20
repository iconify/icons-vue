<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvdre9bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fvdre9bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:check-square-fill" /></template>
