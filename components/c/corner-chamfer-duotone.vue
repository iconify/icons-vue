<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4kc1e1el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4kc1e1el primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-chamfer-duotone" /></template>
