<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knk47snoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knk47snoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-redo" /></template>
