<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vztdlcjho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vztdlcjho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:briefcase-line" /></template>
