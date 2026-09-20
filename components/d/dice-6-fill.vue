<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0u167zly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0u167zly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-6-fill" /></template>
