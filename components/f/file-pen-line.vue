<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3g732bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3g732bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-pen-line" /></template>
