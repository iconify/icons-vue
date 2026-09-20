<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-7og1lim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-7og1lim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:json-alt-4-line" /></template>
