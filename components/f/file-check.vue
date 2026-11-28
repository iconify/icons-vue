<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oni3gky3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oni3gky3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-check" /></template>
