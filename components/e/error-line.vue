<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvpo34bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvpo34bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:error-line" /></template>
