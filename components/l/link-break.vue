<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ol2bc_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ol2bc_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:link-break" /></template>
