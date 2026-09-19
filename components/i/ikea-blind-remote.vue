<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jajccobke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jajccobke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-blind-remote" /></template>
