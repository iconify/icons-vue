<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0cks-b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0cks-b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-down" /></template>
