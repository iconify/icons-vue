<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idh2j0bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idh2j0bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-x-fill" /></template>
