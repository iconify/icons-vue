<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2nposhfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2nposhfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:apps" /></template>
