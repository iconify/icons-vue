<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhxhq9bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhxhq9bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizonta-spacing-outline" /></template>
