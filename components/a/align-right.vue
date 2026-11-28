<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c727g52so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c727g52so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:align-right" /></template>
