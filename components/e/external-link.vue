<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhirkpb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hhirkpb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:external-link" /></template>
