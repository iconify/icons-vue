<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w914eacxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w914eacxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cash-register-gloss" /></template>
