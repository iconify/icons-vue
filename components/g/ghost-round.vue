<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke85xxb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke85xxb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ghost-round" /></template>
