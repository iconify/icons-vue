<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viwk9ab1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viwk9ab1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hbo" /></template>
